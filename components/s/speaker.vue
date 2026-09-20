<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nue2cryyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="nue2cryyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:speaker" /></template>
