<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooxqz1bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooxqz1bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sort-solid" /></template>
