<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbbp588xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbbp588xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-bag-01" /></template>
