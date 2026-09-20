<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crd1z6bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="crd1z6bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tty" /></template>
