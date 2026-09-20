<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzm2_nzau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pzm2_nzau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:text-align-right" /></template>
