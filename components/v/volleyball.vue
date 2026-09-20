<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7nww86df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7nww86df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:volleyball" /></template>
