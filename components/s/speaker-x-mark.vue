<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrk520onz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hrk520onz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:speaker-x-mark" /></template>
