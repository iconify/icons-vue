<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uen7qn_0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uen7qn_0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:starburst-minus-outline" /></template>
