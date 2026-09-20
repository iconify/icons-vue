<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm4s1d5tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fm4s1d5tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:stripe" /></template>
