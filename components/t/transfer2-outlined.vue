<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma3conxig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma3conxig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:transfer2-outlined" /></template>
