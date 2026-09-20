<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-u-habfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-u-habfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:robot-excited" /></template>
