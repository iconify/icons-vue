<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf7qcpbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mf7qcpbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-vert-small-filled" /></template>
