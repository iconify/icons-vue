<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld3dvsbdz.css';
import '../../css/c/cvsu0tmol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ld3dvsbdz"/><path class="cvsu0tmol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-user-20-bold" /></template>
