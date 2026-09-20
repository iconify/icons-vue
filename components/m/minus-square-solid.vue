<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1mfxicff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g1mfxicff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:minus-square-solid" /></template>
