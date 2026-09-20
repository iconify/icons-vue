<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti3zyb3xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti3zyb3xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-outline" /></template>
