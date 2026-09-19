<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0-ehhb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d0-ehhb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tram-fill" /></template>
