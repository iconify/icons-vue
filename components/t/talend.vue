<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl9k6ubdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl9k6ubdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:talend" /></template>
