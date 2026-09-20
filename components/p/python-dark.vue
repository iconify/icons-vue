<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iahdx-b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iahdx-b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:python-dark" /></template>
