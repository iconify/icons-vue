<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp8m3bbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp8m3bbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:refresh-solid" /></template>
