<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq2ums2ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq2ums2ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:point-down-solid" /></template>
