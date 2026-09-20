<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt5xtacse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt5xtacse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-desc-24" /></template>
