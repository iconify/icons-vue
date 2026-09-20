<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iebv6s_is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iebv6s_is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:temperature-empty" /></template>
