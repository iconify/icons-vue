<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daypf_7io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="daypf_7io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:shield-outline" /></template>
