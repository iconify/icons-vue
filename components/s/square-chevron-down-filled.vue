<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eca545beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eca545beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-chevron-down-filled" /></template>
