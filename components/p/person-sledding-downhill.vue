<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2m6l6bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f2m6l6bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sledding-downhill" /></template>
