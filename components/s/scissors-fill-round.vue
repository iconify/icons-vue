<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5ovq8b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ovq8b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scissors-fill-round" /></template>
