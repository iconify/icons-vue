<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awdcmv7pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awdcmv7pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sun-moon" /></template>
