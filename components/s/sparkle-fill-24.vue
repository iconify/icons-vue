<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8muuznpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8muuznpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sparkle-fill-24" /></template>
