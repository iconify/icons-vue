<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs8_ejdrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs8_ejdrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:volume-low" /></template>
