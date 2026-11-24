<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a59s1vb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a59s1vb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:toothbrush-filled" /></template>
