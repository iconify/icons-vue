<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um-6ycezm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um-6ycezm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:trash" /></template>
