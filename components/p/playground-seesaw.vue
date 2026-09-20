<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4rm54l-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4rm54l-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playground-seesaw" /></template>
