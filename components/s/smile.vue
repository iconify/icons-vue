<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-v5zjbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z-v5zjbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:smile" /></template>
