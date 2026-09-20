<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wctkk8nsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wctkk8nsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:train" /></template>
