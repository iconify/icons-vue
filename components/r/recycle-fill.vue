<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkb28cc2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkb28cc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:recycle-fill" /></template>
