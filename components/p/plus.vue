<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz-k09b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz-k09b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:plus" /></template>
