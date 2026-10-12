<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug5nw9bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug5nw9bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shirt-filled" /></template>
