<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk40e1b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk40e1b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:yen-waves-solid" /></template>
