<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4qxmqbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="d4qxmqbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:registered" /></template>
