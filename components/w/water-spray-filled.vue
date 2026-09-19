<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9bxb7pml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9bxb7pml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:water-spray-filled" /></template>
