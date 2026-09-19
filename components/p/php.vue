<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi8nvx12u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xi8nvx12u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:php" /></template>
