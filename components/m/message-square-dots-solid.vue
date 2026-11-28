<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t04in-bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t04in-bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-dots-solid" /></template>
