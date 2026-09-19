<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9660gbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w9660gbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:music" /></template>
