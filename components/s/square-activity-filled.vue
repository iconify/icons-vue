<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fup3y25nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fup3y25nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-activity-filled" /></template>
