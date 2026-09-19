<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skz3znhmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skz3znhmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-left-02" /></template>
