<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5vn-kbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5vn-kbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:protocol" /></template>
