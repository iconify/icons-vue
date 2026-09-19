<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiaixgbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiaixgbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rocket-filled" /></template>
