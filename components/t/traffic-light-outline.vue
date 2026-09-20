<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za8-l6cso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za8-l6cso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:traffic-light-outline" /></template>
