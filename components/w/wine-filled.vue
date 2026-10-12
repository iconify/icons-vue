<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1w1afvdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1w1afvdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wine-filled" /></template>
