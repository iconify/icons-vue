<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp3_9h6db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lp3_9h6db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:navigation-right" /></template>
