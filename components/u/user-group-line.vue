<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ne00ukbgp.css';
import '../../css/o/o4zjqdqds.css';
import '../../css/z/z6nfzqklw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ne00ukbgp"/><path class="o4zjqdqds"/><path class="z6nfzqklw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:user-group-line" /></template>
