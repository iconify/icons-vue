<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxghsl_ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wxghsl_ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:wlan" /></template>
