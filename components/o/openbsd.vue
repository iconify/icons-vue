<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_ek6sqpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_ek6sqpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:openbsd" /></template>
