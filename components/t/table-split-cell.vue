<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpkw0qzse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpkw0qzse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-split-cell" /></template>
