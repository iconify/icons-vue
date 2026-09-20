<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1wg31bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v1wg31bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:star-filled" /></template>
