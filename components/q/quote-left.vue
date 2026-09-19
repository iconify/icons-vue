<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md8i9fb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="md8i9fb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:quote-left" /></template>
