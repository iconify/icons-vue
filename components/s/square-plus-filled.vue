<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seimh3bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seimh3bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-plus-filled" /></template>
