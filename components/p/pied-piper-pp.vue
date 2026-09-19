<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw7jycbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gw7jycbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:pied-piper-pp" /></template>
