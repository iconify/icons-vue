<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deb2onban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="deb2onban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:music" /></template>
