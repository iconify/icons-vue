<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op0u8qj4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op0u8qj4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sigma" /></template>
