<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yik03xb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yik03xb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:minimize" /></template>
