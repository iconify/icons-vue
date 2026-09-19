<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb-y9accw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fb-y9accw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sim-card" /></template>
