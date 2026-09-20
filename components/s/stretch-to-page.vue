<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4b55rbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4b55rbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stretch-to-page" /></template>
