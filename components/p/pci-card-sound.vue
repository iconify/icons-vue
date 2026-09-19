<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c-c82bbdh.css';
import '../../css/c/co9ypkbrw.css';
import '../../css/r/r301wefvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="c-c82bbdh"/><path class="co9ypkbrw"/><path class="r301wefvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pci-card-sound" /></template>
