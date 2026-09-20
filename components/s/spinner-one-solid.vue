<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvbfs2b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvbfs2b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:spinner-one-solid" /></template>
