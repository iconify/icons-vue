<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz0s2ac1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kz0s2ac1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sencho-dark" /></template>
