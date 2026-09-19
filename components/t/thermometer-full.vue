<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj97-rzku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gj97-rzku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:thermometer-full" /></template>
