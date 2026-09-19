<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-jp0obey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-jp0obey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:view-columns" /></template>
