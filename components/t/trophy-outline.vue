<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk877rgaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nk877rgaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:trophy-outline" /></template>
