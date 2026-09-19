<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y83u2k-am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y83u2k-am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:spanner-filled" /></template>
