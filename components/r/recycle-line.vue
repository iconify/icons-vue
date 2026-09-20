<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfh0tyb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfh0tyb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:recycle-line" /></template>
