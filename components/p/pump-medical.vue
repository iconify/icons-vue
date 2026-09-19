<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adjk5db7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="adjk5db7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:pump-medical" /></template>
