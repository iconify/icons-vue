<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh7vgbb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kh7vgbb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-left-outline" /></template>
