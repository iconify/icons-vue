<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4sqbf30h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4sqbf30h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:yen-circle-solid" /></template>
