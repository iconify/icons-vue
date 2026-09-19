<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk0r7efoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk0r7efoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:square-outline" /></template>
