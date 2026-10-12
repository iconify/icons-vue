<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyfy5q2jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yyfy5q2jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:vote-filled" /></template>
