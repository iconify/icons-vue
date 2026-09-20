<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f07p2fb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f07p2fb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:surrealdb" /></template>
