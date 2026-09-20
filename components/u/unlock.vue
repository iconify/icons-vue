<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg792jbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tg792jbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:unlock" /></template>
