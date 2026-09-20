<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olo1jzb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="olo1jzb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:money-bag-outline" /></template>
