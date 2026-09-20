<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_732bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_732bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:path-solid" /></template>
