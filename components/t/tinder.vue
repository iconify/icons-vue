<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la86vc54v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="la86vc54v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tinder" /></template>
