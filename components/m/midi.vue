<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuvjg7bnh.css';
import '../../css/b/bb-8rwkou.css';
import '../../css/i/iic0_9tig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<g class="kuvjg7bnh"><path class="bb-8rwkou"/><path class="iic0_9tig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:midi" /></template>
