<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdkp318ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdkp318ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:usd" /></template>
