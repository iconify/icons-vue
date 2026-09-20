<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anbgv1blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anbgv1blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mwc" /></template>
