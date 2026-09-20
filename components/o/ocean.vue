<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw8854niw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw8854niw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ocean" /></template>
