<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmy194hqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmy194hqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:users-info" /></template>
