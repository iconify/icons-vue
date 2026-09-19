<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f45aa6gqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f45aa6gqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:merge-right" /></template>
