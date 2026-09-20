<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f01lhjzea.css';
import '../../css/k/k2jkwyg1s.css';
import '../../css/n/n7it1melf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="f01lhjzea"/><path clip-rule="evenodd" class="k2jkwyg1s"/><path class="n7it1melf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:object-scan-filled" /></template>
