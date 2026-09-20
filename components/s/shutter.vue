<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmofk934i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mmofk934i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:shutter" /></template>
