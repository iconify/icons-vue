<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0tx1tbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0tx1tbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-case-title" /></template>
