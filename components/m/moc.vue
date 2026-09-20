<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fukygwbuq"/><path class="f68zj0bly"/><path class="bupmhj43d"/><path class="raflolbhv"/><path class="i0kugym2n"/><path class="mb68vtb_w"/><path class="s71n2lbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:moc" /></template>
<style>
.bupmhj43d {
  fill: var(--svg-color--36c7ce, #36c7ce);
  d: path("M12 20.437a8.438 8.438 0 1 0 0-16.875a8.438 8.438 0 0 0 0 16.875");
}

.f68zj0bly {
  fill: var(--svg-color--4f97a5, #4f97a5);
  d: path("M21 12a9 9 0 0 1-18 0z");
}

.ft5dv1b6b {
  fill: none;
}

.fukygwbuq {
  fill: var(--svg-color--9ce3e5, #9ce3e5);
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.i0kugym2n {
  fill: var(--svg-color--3ab1d3, #3ab1d3);
  d: path("M20.437 12c0-2.953-3.64-7.875-8.437-7.875c-4.798 0-8.437 4.494-8.437 7.875a8.437 8.437 0 1 1 16.874 0");
}

.mb68vtb_w {
  fill: var(--svg-color--28808e, #28808e);
  d: path("M7.933 11.23V8.327h1.85l2.116 3.47l2.08-3.47h1.958v2.903l1.688-.265l.225.265V12h-1.913v.805l1.682-.265l.225.265v.787h-1.907v2.616h-1.726l-.225-.27l.225-4.708l-2.363 3.206l-2.205-3.206v4.978h-1.62l-.298-.27l.208-2.346H6.021l-.208-.27l.208-.517h1.912v-.822H6.021l-.208-.264l.208-.49z");
}

.raflolbhv {
  fill: var(--svg-color--359bb1, #359bb1);
  d: path("m12.956 20.944l-5.23-5.007l1.821-5.996l2.104 2.385l4.078-4.264l5.203 5.063a9.3 9.3 0 0 1-1.788 4.37a9.18 9.18 0 0 1-6.188 3.449");
}

.s71n2lbku {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M7.725 10.965V8.063H9.66l2.025 3.324l2.07-3.325h1.969v2.903h1.9v.754H15.73v.815h1.896v.788H15.73v2.615h-1.743v-4.972l-2.307 3.217l-2.25-3.217v4.972H7.725v-2.615H5.813v-.788h1.912v-.815H5.813v-.754z");
}

</style>
