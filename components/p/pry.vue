<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tkdygxafx"><path class="fb5xcebam"/><path class="nv27zybry"/><path class="wkh_oc6uf"/><path class="ohib8cx2q"/><path class="r6ixqc5yl"/><path class="mbzwv17ik"/><path class="uz_jicbrt"/><path class="e0odh9ule"/><path class="xrs76xzvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pry" /></template>
<style>
.e0odh9ule {
  d: path("M8 7.17q.238-.194.5-.365v3.445H5.943c.05-.16.1-.32.16-.475H8z");
}

.fb5xcebam {
  d: path("M3 17.75h18v.5H3zm0-1h18v.5H3zm14.66-7.5a6 6 0 0 0-.275-.5H17V8.2c-.155-.2-.32-.395-.5-.575V9.25z");
}

.mbzwv17ik {
  d: path("M10 6.07q.246-.08.5-.144v6.325H5.685a6 6 0 0 1 0-.5H10z");
}

.nv27zybry {
  d: path("M15.501 6.8c.175.12.34.24.5.37v2.58l1.885.006q.096.24.17.495h-2.555z");
}

.ohib8cx2q {
  d: path("M13.5 5.926q.254.061.5.145v5.68h4.31q.012.25.005.5h-4.816z");
}

.r6ixqc5yl {
  d: path("M12.5 5.75c.17.015.335.05.5.075v6.925h5.28q-.023.254-.075.5H12.5zm-1.5.075c.165-.025.33-.06.5-.075v7.5H5.795a4 4 0 0 1-.075-.5H11z");
}

.tkdygxafx {
  fill: var(--svg-color--eaeae8, #eaeae8);
}

.uz_jicbrt {
  d: path("M9 6.5c.165-.084.335-.17.51-.244v4.995H5.73c.025-.17.05-.335.085-.5H9z");
}

.wkh_oc6uf {
  d: path("M14.49 6.256q.264.114.51.25v4.245h3.186c.035.165.06.33.085.5h-3.78z");
}

.xrs76xzvs {
  d: path("M7 8.2c.155-.2.32-.395.5-.575V9.25H6.34c.085-.17.175-.34.275-.5H7zm-.925 6.05a6 6 0 0 1-.165-.5h12.18c-.05.17-.1.335-.165.5zm.475 1a5 5 0 0 1-.265-.5h11.43c-.08.17-.17.34-.265.5zm.725 1a7 7 0 0 1-.4-.5h10.25q-.189.261-.4.5z");
}

</style>
