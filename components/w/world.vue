<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1sj9daot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="h1sj9daot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:world" /></template>
