<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iapr2gepq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iapr2gepq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:welcome-learn-more" /></template>
