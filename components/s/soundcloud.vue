<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7c9n1blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1085,"height":614};
const content = `<path class="p7c9n1blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:soundcloud" /></template>
