<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8p0ejb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8p0ejb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sign-out" /></template>
