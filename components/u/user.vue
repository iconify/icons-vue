<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs47dhnyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xs47dhnyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:user" /></template>
