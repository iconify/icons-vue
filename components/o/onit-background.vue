<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mtaw57bwl"/><path clip-rule="evenodd" class="iv9m78bhp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:onit-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iv9m78bhp {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.894 13.873h1.021l.34-1.362h.681l.273-1.021h-.722l.068-.51h.838l.163-.852h-1.981zm-2.383-3.745l-.418 2.846c-.058.3.081.899 1.106.899c1.021 0 1.33-.6 1.355-.899l.51-2.846h-1.021l-.391 2.54c-.01.082-.055.177-.29.184c-.238.006-.197-.17-.17-.293l.357-2.43zm-3.234 3.745l.681-3.745h1.178c.34-.01 1.008.157.94.902c-.069.75-.566.9-.804.882c.221.044.627.31.558.94s-.66.936-.96 1.02zm1.274-2.26l.085-.746c.184 0 .534.072.442.36c-.088.287-.388.375-.527.386m-.252 1.579l.17-.851c.204 0 .545.099.442.409c-.098.313-.463.432-.612.442m-3.064-3.064l-.68 3.745h.68l.34-1.702l.426 1.702h.766l.68-3.745h-.85l-.34 1.702l-.341-1.702zm-3.097 1.165c-.195.714-.334 2.226.677 2.553c.405.108 1.297-.069 1.63-1.645c.147-.575.205-1.79-.762-2.052a1.7 1.7 0 0 0-.524 0zm.827.663c.027-.323.15-.97.429-.977c.279-.006.234.647.177.977c-.051.314-.208.967-.446 1.056c-.239.095-.205-.664-.16-1.056m12.765 1.917l.765-.681l.174-.68h.698l.279-1.022h-.735l.068-.51h.86l.161-.852h-2.025l-.698 3.745z");
}

.mtaw57bwl {
  fill: var(--svg-color--3662af, #3662af);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
