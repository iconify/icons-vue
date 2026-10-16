<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5dhy6b4r.css';
import '../../css/o/o0s_5jy_f.css';
import '../../css/f/fn5st7b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f5dhy6b4r"/><path class="o0s_5jy_f"/><path class="fn5st7b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-tanker-20-bold" /></template>
