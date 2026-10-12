<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnnbb5bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnnbb5bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:squircle-filled" /></template>
