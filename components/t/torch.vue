<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw8ihx1hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":1024};
const content = `<path class="hw8ihx1hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:torch" /></template>
