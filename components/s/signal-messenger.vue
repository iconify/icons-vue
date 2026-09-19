<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1aafdc0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p1aafdc0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:signal-messenger" /></template>
