<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs_njs9ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs_njs9ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:testcafe" /></template>
