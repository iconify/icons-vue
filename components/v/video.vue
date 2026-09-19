<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6a1je0ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6a1je0ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:video" /></template>
