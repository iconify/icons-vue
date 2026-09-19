<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v00xwjhce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v00xwjhce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:person-add" /></template>
