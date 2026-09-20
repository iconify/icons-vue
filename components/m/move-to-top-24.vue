<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyqr6ubaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyqr6ubaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:move-to-top-24" /></template>
