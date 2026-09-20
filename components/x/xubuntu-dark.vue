<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6g0-4b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v6g0-4b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xubuntu-dark" /></template>
