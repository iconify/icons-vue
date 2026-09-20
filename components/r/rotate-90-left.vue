<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su_59fbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="su_59fbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rotate-90-left" /></template>
