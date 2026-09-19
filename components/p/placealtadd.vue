<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joalz1tbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="joalz1tbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:placealtadd" /></template>
