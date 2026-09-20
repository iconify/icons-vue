<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r07fs7qse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r07fs7qse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:openai" /></template>
