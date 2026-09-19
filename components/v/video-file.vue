<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoontqb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uoontqb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:video-file" /></template>
