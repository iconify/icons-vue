<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahlorjbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahlorjbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:money" /></template>
