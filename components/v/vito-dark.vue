<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaytvybfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kaytvybfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vito-dark" /></template>
