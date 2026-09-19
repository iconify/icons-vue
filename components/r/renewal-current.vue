<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubf4_r3tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ubf4_r3tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:renewal-current" /></template>
