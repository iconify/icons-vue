<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wezzffb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wezzffb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:sun-filled" /></template>
