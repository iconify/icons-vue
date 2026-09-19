<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3p-e2bku.css';
import '../../css/r/rrl70bbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s3p-e2bku"/><path class="rrl70bbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rule-cancelled" /></template>
