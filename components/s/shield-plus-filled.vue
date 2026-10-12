<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnwommb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jnwommb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-plus-filled" /></template>
