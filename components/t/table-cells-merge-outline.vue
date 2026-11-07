<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd9a8-uca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rd9a8-uca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-cells-merge-outline" /></template>
