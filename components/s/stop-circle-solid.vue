<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b911mpgha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b911mpgha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:stop-circle-solid" /></template>
