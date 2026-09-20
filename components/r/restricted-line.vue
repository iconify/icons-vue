<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n312wjbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n312wjbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:restricted-line" /></template>
