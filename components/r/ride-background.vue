<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qpiab5b6z"/><path clip-rule="evenodd" class="twvnyabhn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ride-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qpiab5b6z {
  fill: var(--svg-color--f11e99, #f11e99);
  d: path("M24 0H0v24h24z");
}

.twvnyabhn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.23 11.988c.218-.274.43-.644.624-1.224c.696-2.06-1.179-5.259-4.43-5.347c-1.269-.8-2.91-1.326-5.004-1.406c-3.696-.14-4.794 1.032-4.88 2.522a2.9 2.9 0 0 0-.856.669C3.57 8.484 4 10.219 4.702 11.597c.177-3.48 3.07-6.235 6.608-6.235c3.646 0 6.61 2.936 6.61 6.568c0 3.638-2.964 6.569-6.61 6.569a6.59 6.59 0 0 1-6.18-4.233c-.526.69-.897 1.646-.479 2.723v.004c.673 1.734 2.266 2.238 3.547 2.246c2.573 1.217 4.47.712 5.775.276a3.7 3.7 0 0 0 1.224-.709l.037-.006l.015-.014c1.473-.261 2.831-.948 3.537-2.72c.383-.967.59-2.441.434-4.03l.013-.016v-.005zm-12.998-.053C6.232 9.159 8.5 6.9 11.31 6.9c2.809 0 5.072 2.259 5.072 5.03s-2.268 5.03-5.073 5.03c-2.809 0-5.077-2.258-5.077-5.025");
}

</style>
