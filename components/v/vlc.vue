<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8-tbpb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p8-tbpb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:vlc" /></template>
