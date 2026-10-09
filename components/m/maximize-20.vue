<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sos5epbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sos5epbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:maximize-20" /></template>
