<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmq4v6njp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cmq4v6njp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-funnel" /></template>
