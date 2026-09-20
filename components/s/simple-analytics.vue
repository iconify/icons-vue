<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzyxvbbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzyxvbbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:simple-analytics" /></template>
