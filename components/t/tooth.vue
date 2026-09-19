<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvjm0pbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvjm0pbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth" /></template>
