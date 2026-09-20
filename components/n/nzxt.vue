<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irhaz3qoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irhaz3qoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nzxt" /></template>
