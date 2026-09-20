<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pmpskaclj"/><path class="unf_74bge"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rvn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pmpskaclj {
  fill: var(--svg-color--df5d44, #df5d44);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.unf_74bge {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.355 16.978L7.156 20l2.67-12.274zm.09-.022l2.55.03l-4.072-9.222zm2.797-.21l1.956-7.258l-.742-.9zm-.945-11.382L10.073 7.54l4.708-1.523zm-.405 0l-2.002.075l-.3.825zM9.976 7.681l4.138 9.26l1.26-8.502zm.614-1.32l2.55-.997l-3.164 2.13zm.33-1.05l.645-.697l1.47.645zm.742-.779l1.013-.465l1.29 1.477zM12.742 4h1.08l.6.652zm1.454 1.642l.255-.773l.263 1.02zM10.156 7.6l5.158.704l-.51-2.174zm4.7-1.665l-.33-1.207l2.318.682zm-.48-1.132l-.284.772l-1.2-1.417z");
}

</style>
