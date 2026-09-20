<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="knbftoyig"/><path class="git08obdy"/><path class="mup_zen9k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nblu-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.git08obdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.96 17.47c2.408.66 5.009-1.257 5.809-4.281c.792-3.017-.516-6.001-2.929-6.658c-1.99-.545-4.112.67-5.24 2.814a3 3 0 0 1 .392.635c.608 1.249.904 1.788 1.192 2.02a1.6 1.6 0 0 0 .016-.372c-.02-.436-.256-1.084-.6-1.844c-.205-.39-.202-.565-.2-.717v-.043c0-.164.296-.624 1.376-.624c.54 0 1.016.132 1.24.624c.224.496.348 4.837-.256 5.917c-.16.3-.92.66-1.688.66h-.017c-.19.001-.5.003-.903-1.084C11.74 13.397 11.148 12 10.928 12c-.088 0-.122.272-.128.571c0 .496.054.979.159 1.436l.077.22c.086.244.195.552.25.781c.53 1.213 1.462 2.13 2.674 2.46");
}

.knbftoyig {
  fill: var(--svg-color--0071c1, #0071c1);
  d: path("M24 0H0v24h24z");
}

.mup_zen9k {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.04 17.47c-2.408.66-5.009-1.257-5.809-4.281c-.792-3.017.516-6.001 2.929-6.658c2.023-.554 4.181.71 5.294 2.92q.043.135.146.333q.075.167.144.327a7 7 0 0 1 .43 1.881c-.285-.236-.581-.778-1.182-2.012c-.57-1.189-1.205-1.184-1.644-1.18h-.068c-.444 0-1.145.032-1.497.296H8.78c-.28.212-.368 2-.38 2.957c0 2.172.16 3.124.32 3.488c.16.36.476.46 1.08.46c1.08 0 1.525-.492 1.525-.76c0-.199-.167-.67-.288-1.013c-.037-.105-.07-.198-.092-.267c-.096-.296-.144-.972-.144-1.3c0-.332.032-.66.128-.66c.22 0 .812 1.396 1.224 2.516c.15.402.286.655.408.814c-.546 1.053-1.418 1.838-2.52 2.138");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
