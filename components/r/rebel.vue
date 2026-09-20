<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxvcj4bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lxvcj4bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:rebel" /></template>
