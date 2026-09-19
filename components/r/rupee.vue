<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8oie8bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8oie8bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rupee" /></template>
