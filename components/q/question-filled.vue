<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk4lkh9jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uk4lkh9jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:question-filled" /></template>
