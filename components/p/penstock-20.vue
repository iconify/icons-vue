<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh3xhwb0f.css';
import '../../css/g/gfokxvboe.css';
import '../../css/m/m42n8zsrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uh3xhwb0f"/><path class="gfokxvboe"/><path class="m42n8zsrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:penstock-20" /></template>
