<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a7wpunw6b.css';
import '../../css/d/d4__7jb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a7wpunw6b"/><path clip-rule="evenodd" class="d4__7jb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:visa-solid" /></template>
