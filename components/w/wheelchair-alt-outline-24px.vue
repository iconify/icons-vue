<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl3fnxbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hl3fnxbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:wheelchair-alt-outline-24px" /></template>
