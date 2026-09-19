<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jswr-7bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jswr-7bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:stats-down-square-solid" /></template>
