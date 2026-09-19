<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6y1ldb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n6y1ldb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:usb" /></template>
