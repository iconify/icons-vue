<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf6uoi_3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lf6uoi_3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:mobile-phone" /></template>
