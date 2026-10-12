<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1q4onb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1q4onb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sun-dim-filled" /></template>
