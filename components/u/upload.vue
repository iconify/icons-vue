<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuy6n6bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuy6n6bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:upload" /></template>
