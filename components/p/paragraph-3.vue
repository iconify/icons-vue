<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdhep31tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdhep31tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:paragraph-3" /></template>
