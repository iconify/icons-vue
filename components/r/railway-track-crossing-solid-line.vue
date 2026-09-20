<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5w8kubkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h5w8kubkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:railway-track-crossing-solid-line" /></template>
