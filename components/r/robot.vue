<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/k/k-y9zgp3c.css';
import '../../css/e/ebpla5b_i.css';
import '../../css/b/brg541bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="k-y9zgp3c"/><path class="ebpla5b_i"/><path class="brg541bpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:robot" /></template>
