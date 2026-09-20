<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-k5bccei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-k5bccei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:middleware" /></template>
