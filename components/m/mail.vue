<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzq0fibel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzq0fibel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:mail" /></template>
