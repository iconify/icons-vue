<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olsxm8btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olsxm8btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wireless-cloud-access" /></template>
