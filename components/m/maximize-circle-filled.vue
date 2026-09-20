<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oody99b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oody99b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:maximize-circle-filled" /></template>
