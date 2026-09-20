<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwl_y62-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwl_y62-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:toggle-right-solid" /></template>
