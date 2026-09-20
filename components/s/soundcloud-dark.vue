<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9l9obcqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":75,"height":33.51};
const content = `<path class="s9l9obcqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:soundcloud-dark" /></template>
