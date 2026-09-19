<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm8jlwbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm8jlwbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-distribute-center-filled" /></template>
