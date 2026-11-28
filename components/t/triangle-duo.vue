<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id5i4irup.css';
import '../../css/q/qi6vm4w9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id5i4irup secondary"/><path class="primary qi6vm4w9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-duo" /></template>
