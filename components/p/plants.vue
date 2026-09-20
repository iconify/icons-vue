<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je9q0nbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="je9q0nbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plants" /></template>
