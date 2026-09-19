<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0bsct1rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="h0bsct1rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:snapchat" /></template>
