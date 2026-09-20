<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1jznez-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-2.5};
const content = `<path class="v1jznez-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:refresh-reverse" /></template>
