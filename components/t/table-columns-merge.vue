<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsuqvormg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsuqvormg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-columns-merge" /></template>
