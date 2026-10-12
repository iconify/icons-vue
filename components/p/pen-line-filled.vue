<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfmj2etah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfmj2etah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pen-line-filled" /></template>
