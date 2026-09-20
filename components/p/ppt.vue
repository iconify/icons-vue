<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa4glvbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa4glvbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ppt" /></template>
