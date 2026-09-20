<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae-3ksbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae-3ksbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-block-filled" /></template>
