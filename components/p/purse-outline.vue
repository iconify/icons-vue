<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muz_lmbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="muz_lmbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:purse-outline" /></template>
