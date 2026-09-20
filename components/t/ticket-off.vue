<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fodvy5bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fodvy5bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ticket-off" /></template>
