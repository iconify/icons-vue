<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2zxg1bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2zxg1bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-crack-filled" /></template>
