<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4v2nxbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="x4v2nxbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:supple" /></template>
