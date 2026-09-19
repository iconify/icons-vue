<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3c-jwbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s3c-jwbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:pinterest-with-circle" /></template>
