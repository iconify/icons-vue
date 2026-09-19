<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp56aqbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="lp56aqbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:plug" /></template>
