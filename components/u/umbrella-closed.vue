<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s46vpd6ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s46vpd6ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:umbrella-closed" /></template>
