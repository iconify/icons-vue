<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c4z116bnm.css';
import '../../css/f/ftrssobwy.css';
import '../../css/l/lv9n1n5sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c4z116bnm"/><path class="ftrssobwy"/><path class="lv9n1n5sk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-square-bold-duotone" /></template>
