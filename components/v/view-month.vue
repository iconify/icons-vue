<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9-2m5u6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9-2m5u6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:view-month" /></template>
