<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th-w9lb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="th-w9lb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:musical-keyboard-filled" /></template>
