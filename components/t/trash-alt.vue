<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqffoys6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqffoys6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trash-alt" /></template>
