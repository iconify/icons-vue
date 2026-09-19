<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fidnqcqve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fidnqcqve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:navigation-2-fill" /></template>
