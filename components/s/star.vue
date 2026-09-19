<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxrbbfz1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="kxrbbfz1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:star" /></template>
