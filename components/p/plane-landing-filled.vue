<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zni3kgb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zni3kgb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:plane-landing-filled" /></template>
