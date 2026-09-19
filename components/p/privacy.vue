<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-i5jcr0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l-i5jcr0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:privacy" /></template>
