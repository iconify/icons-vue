<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k44leqden.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k44leqden"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-warning-bold" /></template>
