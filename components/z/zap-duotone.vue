<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqzxvhb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zqzxvhb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zap-duotone" /></template>
