<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igff9lbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="igff9lbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:merge" /></template>
