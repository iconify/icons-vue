<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gya7n-bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gya7n-bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:multiple-musical-notes" /></template>
