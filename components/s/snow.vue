<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j31cb_byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j31cb_byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:snow" /></template>
