<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlx_r6b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zlx_r6b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:meetup" /></template>
