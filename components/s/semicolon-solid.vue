<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl6yjpv1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl6yjpv1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:semicolon-solid" /></template>
