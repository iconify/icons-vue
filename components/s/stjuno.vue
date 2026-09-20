<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca70d8nob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca70d8nob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:stjuno" /></template>
