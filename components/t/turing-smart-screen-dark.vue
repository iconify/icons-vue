<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyqdx1fbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gyqdx1fbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:turing-smart-screen-dark" /></template>
