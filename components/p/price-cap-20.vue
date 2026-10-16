<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km2fl-ght.css';
import '../../css/v/v-6vjfmba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="km2fl-ght"/><path class="v-6vjfmba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-cap-20" /></template>
