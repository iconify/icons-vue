<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7iay7b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7iay7b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:receipt" /></template>
