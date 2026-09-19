<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzi7qo5ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzi7qo5ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:share-ios-export" /></template>
