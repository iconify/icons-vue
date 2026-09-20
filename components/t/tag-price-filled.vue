<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt2k5rb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mt2k5rb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag-price-filled" /></template>
