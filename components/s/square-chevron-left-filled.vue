<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iae1v6etf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iae1v6etf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-chevron-left-filled" /></template>
