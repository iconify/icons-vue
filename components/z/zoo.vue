<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki_xp1ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ki_xp1ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:zoo" /></template>
