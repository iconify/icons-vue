<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4ifs6byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4ifs6byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:writing-sign-filled" /></template>
