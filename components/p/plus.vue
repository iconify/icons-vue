<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eazv3ebih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eazv3ebih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:plus" /></template>
