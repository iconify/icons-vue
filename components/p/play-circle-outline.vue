<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbwxjo--h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbwxjo--h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-circle-outline" /></template>
