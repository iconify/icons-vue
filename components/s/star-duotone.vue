<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7bv47brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary t7bv47brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:star-duotone" /></template>
