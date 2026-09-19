<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2z9bdfzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n2z9bdfzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-tumblr-outline" /></template>
