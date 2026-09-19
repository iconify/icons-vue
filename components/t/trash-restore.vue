<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c25_9ibwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="c25_9ibwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:trash-restore" /></template>
