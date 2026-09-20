<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od9ez2buj.css';
import '../../css/h/hstvx30-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od9ez2buj"/><path class="hstvx30-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:payment-link" /></template>
