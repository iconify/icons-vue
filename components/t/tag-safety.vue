<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkbhseb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkbhseb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-safety" /></template>
