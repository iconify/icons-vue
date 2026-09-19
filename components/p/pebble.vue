<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1z1kiznu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="h1z1kiznu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pebble" /></template>
