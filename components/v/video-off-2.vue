<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1jhk9bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v1jhk9bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:video-off-2" /></template>
