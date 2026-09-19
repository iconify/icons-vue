<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxy1yxb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yxy1yxb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-android" /></template>
