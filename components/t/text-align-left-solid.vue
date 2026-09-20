<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndmtz2bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndmtz2bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:text-align-left-solid" /></template>
