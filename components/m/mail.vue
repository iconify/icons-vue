<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd1_v8oue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd1_v8oue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:mail" /></template>
