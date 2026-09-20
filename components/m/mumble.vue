<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqxf8yvyj.css';
import '../../css/f/ffqw7f7px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gqxf8yvyj"/><path class="ffqw7f7px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mumble" /></template>
