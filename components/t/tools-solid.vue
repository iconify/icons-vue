<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_pb7vbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a_pb7vbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tools-solid" /></template>
