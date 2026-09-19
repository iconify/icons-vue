<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtmjq4l9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtmjq4l9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:volume-down-solid" /></template>
