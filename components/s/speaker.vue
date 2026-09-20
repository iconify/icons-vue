<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0jw8gyfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="m0jw8gyfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:speaker" /></template>
