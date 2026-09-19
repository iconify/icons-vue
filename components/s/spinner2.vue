<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzj3t6uud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jzj3t6uud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:spinner2" /></template>
