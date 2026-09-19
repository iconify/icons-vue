<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osbk2_69o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="osbk2_69o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-whatsapp" /></template>
