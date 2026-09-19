<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhn1_ob-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lhn1_ob-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shield-shaded" /></template>
