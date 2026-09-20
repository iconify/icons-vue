<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcco9vbwq.css';
import '../../css/l/l5p8g7bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcco9vbwq"/><path class="l5p8g7bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:messages-people-person-bubble-square-2" /></template>
