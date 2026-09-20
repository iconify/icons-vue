<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my7a5ub9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="my7a5ub9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:stereo-16" /></template>
