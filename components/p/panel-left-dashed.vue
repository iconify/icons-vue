<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otbfd4iee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otbfd4iee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:panel-left-dashed" /></template>
