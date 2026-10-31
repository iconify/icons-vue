<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/n44arpewq.css';
import '../../css/c/c6y59zbkx.css';
import '../../css/z/z7mdej9ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="n44arpewq wm-shadow"/><path class="c6y59zbkx wm-shadow"/><path class="z7mdej9ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:rainbow" /></template>
