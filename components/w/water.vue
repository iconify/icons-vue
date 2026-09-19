<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyfd32boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eyfd32boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:water" /></template>
