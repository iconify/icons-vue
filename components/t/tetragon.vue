<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh11y8bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh11y8bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:tetragon" /></template>
