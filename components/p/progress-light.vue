<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyj4jwbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyj4jwbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:progress-light" /></template>
