<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3l7hbioh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3l7hbioh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:video" /></template>
