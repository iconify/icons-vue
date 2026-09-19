<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtw5inagp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtw5inagp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:options-fill" /></template>
