<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk3br8gfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jk3br8gfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unraid-dark" /></template>
