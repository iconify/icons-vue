<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yois6lbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yois6lbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:try-it-online" /></template>
