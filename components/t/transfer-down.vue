<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytxgg-b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytxgg-b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:transfer-down" /></template>
