<section id="hoc-krylov-readme">

  <h1>HOC-Krylov Solver</h1>

  <p>
    <strong>HOC-Krylov</strong> is a Poisson equation solver that integrates 
    high-order compact (HOC) finite difference schemes with Krylov subspace 
    iterative methods. The solver is implemented in Fortran and includes 
    multiple sparse matrix storage formats and customized matrix–vector 
    multiplication routines for efficiency.
  </p>

  <h2>Features</h2>
  <ul>
    <li>High-order compact finite difference discretization.</li>
    <li>Multiple Krylov solvers including CG, CGS, BiCGSTAB, CR, and GMRES*.</li>
    <li>Optimized sparse matrix formats: CSR, MSR, ELL, and DIA.</li>
    <li>ILU(0) preconditioned versions of Krylov solvers.</li>
    <li>Structured and unstructured grid support.</li>
    <li>Modular Fortran architecture for easy extension.</li>
  </ul>

  <h2>Repository</h2>
  <p>
    GitHub: 
    <a href="https://github.com/imanfarahbakhsh/HOC-Krylov1.0" target="_blank">
      https://github.com/imanfarahbakhsh/HOC-Krylov1.0
    </a>
  </p>

  <h2>Authors</h2>
  <ul>
    <li>Iman Farahbakhsh</li>
    <li>Benyamin Barani Nia</li>
  </ul>

  <h2>Citation</h2>
  <p>
    If you use this solver in your research, please cite the corresponding paper:<br>
    <em>Farahbakhsh, I., Barani Nia, B., & Dehghan, M. (2025). 
    A Survey on the Performance of Krylov Subspace Methods in High Order Compact 
    Schemes for Solving Poisson’s Equation. Annals of Applied Mathematics.</em>
  </p>

  <h2>License</h2>
  <p>MIT License</p>

</section>
