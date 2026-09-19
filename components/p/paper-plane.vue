<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usrlopbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="usrlopbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:paper-plane" /></template>
