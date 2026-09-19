<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/ti3lcux8x.css';
import '../../css/g/gjjyej82e.css';
import '../../css/a/ae894nmnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ti3lcux8x"/><path clip-rule="evenodd" class="gjjyej82e"/><path clip-rule="evenodd" class="ae894nmnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:volume-up-solid" /></template>
