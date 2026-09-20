<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slaia1q8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slaia1q8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sst" /></template>
