<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuon0ob1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuon0ob1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vv" /></template>
