<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vefu94b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":288,"height":512};
const content = `<path class="vefu94b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mars-stroke-v" /></template>
