<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbuo0fbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbuo0fbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:waves-solid" /></template>
