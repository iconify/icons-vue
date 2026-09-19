<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3zh8p7en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="r3zh8p7en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-fill-12" /></template>
