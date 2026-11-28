<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsppwy8tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsppwy8tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:watering-can-clock" /></template>
