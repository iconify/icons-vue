<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su_apmhpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="su_apmhpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:users-16-solid" /></template>
