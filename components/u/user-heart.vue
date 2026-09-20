<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrh9d6z6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrh9d6z6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-heart" /></template>
