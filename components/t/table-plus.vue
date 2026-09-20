<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axw7n_bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axw7n_bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:table-plus" /></template>
