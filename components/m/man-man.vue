<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf_1rfblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf_1rfblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:man-man" /></template>
