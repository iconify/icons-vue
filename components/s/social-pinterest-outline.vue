<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsl8n5bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsl8n5bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-pinterest-outline" /></template>
