<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w55ukkbng.css';
import '../../css/v/v14jurb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w55ukkbng"/><path class="v14jurb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:satellite-dish-alt" /></template>
