<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjax9hm8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjax9hm8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-chipped-filled" /></template>
