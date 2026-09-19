<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8y9o-byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h8y9o-byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sink" /></template>
