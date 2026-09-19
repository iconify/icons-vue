<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by0hihb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":288,"height":512};
const content = `<path class="by0hihb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:venus" /></template>
