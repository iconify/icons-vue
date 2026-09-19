<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksgk5qbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksgk5qbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medical-kit-filled" /></template>
