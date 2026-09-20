<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGRITs7dIw"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="gr7ha8b8o"/><path class="p3xc6-bpj"/><path class="x9i-ju8ec"/></g></mask></defs><circle mask="url(#SVGRITs7dIw)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:studio-light-front-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.gr7ha8b8o {
  d: path("M13 11a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 2a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.p3xc6-bpj {
  d: path("M9.013 6.508C8.236 5.174 9.197 3.5 10.741 3.5h4.518c1.544 0 2.505 1.674 1.727 3.008L15.24 9.504l-1.73-1.008L15.26 5.5h-4.518l1.748 2.996l-1.728 1.008zm7.974 6.984c.777 1.334-.184 3.008-1.728 3.008h-4.518c-1.544 0-2.505-1.674-1.728-3.008l1.748-2.996l1.728 1.008L10.74 14.5h4.518l-1.748-2.996l1.728-1.008z");
}

.x9i-ju8ec {
  d: path("M9.61 13.296c-1.33.886-3.11-.067-3.11-1.665V8.37c0-1.598 1.78-2.55 3.11-1.665l2.945 1.964L11.667 10l.888 1.332zM10.946 10L8.5 8.369v3.262zm5.444-3.296c1.33-.886 3.11.067 3.11 1.665v3.262c0 1.598-1.78 2.55-3.11 1.665l-2.945-1.964l.888-1.332l-.888-1.332zM15.054 10l2.447 1.631V8.37zm3.36 11.406a1 1 0 0 1-1.32.508L14 20.539v.961a1 1 0 1 1-2 0v-.961l-3.094 1.375a1 1 0 0 1-.812-1.828L12 18.35V16a1 1 0 1 1 2 0v2.35l3.906 1.736a1 1 0 0 1 .508 1.32");
}

</style>
