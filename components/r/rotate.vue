<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb6djtynm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb6djtynm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:rotate" /></template>
