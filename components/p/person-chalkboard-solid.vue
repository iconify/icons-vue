<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mm9qf3b4s.css';
import '../../css/a/axfh34b7v.css';
import '../../css/h/h79p-zbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mm9qf3b4s"/><path class="axfh34b7v"/><path class="h79p-zbnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:person-chalkboard-solid" /></template>
