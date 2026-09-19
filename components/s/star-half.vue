<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e42tj16gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e42tj16gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:star-half" /></template>
