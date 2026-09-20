<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGyDL5jbwo)" class="fzsevvkte"/><path fill="url(#SVGXZnLSbWb)" class="oql1qaclm"/><path fill="url(#SVGExd3JbpU)" class="bd_ac9gks"/><path fill="url(#SVGEQT4rcaW)" class="vpo7tybai"/><defs><linearGradient id="SVGyDL5jbwo" x1="3" x2="19.543" y1="13.932" y2="20.622" gradientUnits="userSpaceOnUse"><stop class="z682eibda"/><stop offset="1" class="nzzmtrekd"/></linearGradient><linearGradient id="SVGXZnLSbWb" x1="18.953" x2="18.331" y1="5.005" y2="17.786" gradientUnits="userSpaceOnUse"><stop class="gh6vh35-h"/><stop offset="1" class="t8t5h6bsx"/></linearGradient><linearGradient id="SVGExd3JbpU" x1="21" x2="4.457" y1="10.068" y2="3.378" gradientUnits="userSpaceOnUse"><stop class="uh7kbcczm"/><stop offset="1" class="uuvb88bad"/></linearGradient><linearGradient id="SVGEQT4rcaW" x1="17.625" x2="19.926" y1="19.023" y2="7.942" gradientUnits="userSpaceOnUse"><stop class="a5wzkyboh"/><stop offset="1" class="nx09iwbcj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strp" /></template>
<style>
.a5wzkyboh {
  stop-color: var(--svg-color--f38f12, #f38f12);
}

.bd_ac9gks {
  d: path("M18.187 5.813A8.56 8.56 0 0 1 21 12.174a8.57 8.57 0 0 1-3.808 7.139c.461-1.03.995-2.52.995-3.724c0-1.992-1.687-5.119-4.5-5.693l-.562.855c-.467-.663-1.687-2.103-2.812-2.56a3.99 3.99 0 0 1 4.218-1.135l-.281.849c.186.281.787.855 1.688.855c1.124 0 2.25-.855 2.25-2.278z");
}

.ft5dv1b6b {
  fill: none;
}

.fzsevvkte {
  d: path("M5.813 18.188A8.56 8.56 0 0 1 3 11.826a8.57 8.57 0 0 1 3.808-7.139c-.461 1.03-.995 2.52-.995 3.724c0 1.992 1.687 5.119 4.5 5.693l.562-.855c.467.663 1.688 2.103 2.813 2.56a4 4 0 0 1-4.22 1.135l.282-.849a2.1 2.1 0 0 0-1.687-.855c-1.126 0-2.25.855-2.25 2.278z");
}

.gh6vh35-h {
  stop-color: var(--svg-color--076eb0, #076eb0);
}

.nx09iwbcj {
  stop-color: var(--svg-color--f09508, #f09508);
}

.nzzmtrekd {
  stop-color: var(--svg-color--0c99d7, #0c99d7);
}

.oql1qaclm {
  d: path("M5.824 8.085a8.56 8.56 0 0 0-1.699 5.136a8.6 8.6 0 0 0 1.367 4.663A8.55 8.55 0 0 1 3 11.826a8.57 8.57 0 0 1 3.808-7.139a11 11 0 0 0-.984 3.398");
}

.t8t5h6bsx {
  stop-color: var(--svg-color--199cd4, #199cd4);
}

.uh7kbcczm {
  stop-color: var(--svg-color--fbb20b, #fbb20b);
}

.uuvb88bad {
  stop-color: var(--svg-color--feff42, #feff42);
}

.vpo7tybai {
  d: path("M18.176 15.913a8.54 8.54 0 0 0 1.699-5.136a8.6 8.6 0 0 0-1.367-4.663A8.55 8.55 0 0 1 21 12.172a8.57 8.57 0 0 1-3.808 7.139c.51-1.072.842-2.22.984-3.398");
}

.z682eibda {
  stop-color: var(--svg-color--0367ab, #0367ab);
}

</style>
