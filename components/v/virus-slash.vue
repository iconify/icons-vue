<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hetfuzv4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hetfuzv4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:virus-slash" /></template>
