<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqehv-afi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jqehv-afi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:ruler-2" /></template>
