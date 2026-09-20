<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdxr_pmzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdxr_pmzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:search-x-solid" /></template>
