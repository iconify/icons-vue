<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ope5wjb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ope5wjb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sorting-a-z-01" /></template>
