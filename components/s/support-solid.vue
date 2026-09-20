<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj4ar5bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj4ar5bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:support-solid" /></template>
