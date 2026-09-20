<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keum6jv7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="keum6jv7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:minus" /></template>
