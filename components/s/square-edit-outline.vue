<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-5sc1bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-5sc1bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-edit-outline" /></template>
