<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcti43xnk.css';
import '../../css/u/uv_ob1bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hcti43xnk"/><path class="uv_ob1bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:rocket-launch-16-solid" /></template>
