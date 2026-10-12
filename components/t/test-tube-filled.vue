<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6te3llwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6te3llwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:test-tube-filled" /></template>
