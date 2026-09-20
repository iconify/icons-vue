<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw4lg9bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw4lg9bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:westerndigital" /></template>
