<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la9_avq4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="la9_avq4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus" /></template>
