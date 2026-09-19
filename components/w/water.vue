<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm1g9rboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="xm1g9rboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:water" /></template>
