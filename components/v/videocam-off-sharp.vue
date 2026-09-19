<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esj_debvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="esj_debvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:videocam-off-sharp" /></template>
