<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz4w4abug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz4w4abug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wireless" /></template>
