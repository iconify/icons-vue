<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akpibvbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akpibvbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tablet-button-fill-round" /></template>
