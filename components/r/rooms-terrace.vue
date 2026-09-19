<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0jcubbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0jcubbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-terrace" /></template>
