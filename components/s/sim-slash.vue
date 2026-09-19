<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp-xggb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sp-xggb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sim-slash" /></template>
