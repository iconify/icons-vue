<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kricpd2si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="kricpd2si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ticket-alt" /></template>
