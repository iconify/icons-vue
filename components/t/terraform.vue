<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3wm-mdki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i3wm-mdki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:terraform" /></template>
