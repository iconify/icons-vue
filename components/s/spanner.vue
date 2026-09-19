<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffn7vc-5q.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZOMjqdzR"><path class="ffn7vc-5q"/></mask></defs><path mask="url(#SVGZOMjqdzR)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:spanner" /></template>
