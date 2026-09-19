<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0v9ddlnx.css';
import '../../css/a/a2og3c3yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0v9ddlnx"/><path class="a2og3c3yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-star-filled" /></template>
