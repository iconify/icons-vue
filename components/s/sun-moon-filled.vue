<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dste_4pjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dste_4pjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sun-moon-filled" /></template>
