<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7xigcc8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="j7xigcc8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:security-26" /></template>
