<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekjy-ml0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ekjy-ml0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:star-slash-fill" /></template>
