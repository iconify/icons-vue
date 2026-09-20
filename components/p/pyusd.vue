<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp7t3jbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yp7t3jbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pyusd" /></template>
