<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/badz66hkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="badz66hkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:slideshare" /></template>
