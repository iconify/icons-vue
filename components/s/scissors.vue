<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu_2nrbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu_2nrbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:scissors" /></template>
