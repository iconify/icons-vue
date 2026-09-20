<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q07717bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q07717bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tugtainer-dark" /></template>
