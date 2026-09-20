<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd8knp7lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zd8knp7lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:redlib-light" /></template>
