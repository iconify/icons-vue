<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlcoxxb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlcoxxb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scooter-filled" /></template>
