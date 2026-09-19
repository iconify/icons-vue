<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k37wizbef.css';
import '../../css/o/otjvghwvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k37wizbef"/><path class="otjvghwvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:network-overlay" /></template>
