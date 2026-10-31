<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkuojebws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkuojebws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:shield-alert" /></template>
