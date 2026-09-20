<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2z8qxnta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1227};
const content = `<path class="s2z8qxnta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:x-formerly-twitter-light" /></template>
