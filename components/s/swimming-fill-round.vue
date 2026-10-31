<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob2rxub8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob2rxub8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swimming-fill-round" /></template>
