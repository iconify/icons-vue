<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq8vz1bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gq8vz1bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pen-cancelled" /></template>
