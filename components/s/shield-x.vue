<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po468yrgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po468yrgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-x" /></template>
