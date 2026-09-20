<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiiq-jbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oiiq-jbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ticket-alt" /></template>
