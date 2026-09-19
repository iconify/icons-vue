<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_9rovs-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="f_9rovs-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:skype" /></template>
