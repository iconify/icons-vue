<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh7ay8b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh7ay8b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:screenshot-filled" /></template>
