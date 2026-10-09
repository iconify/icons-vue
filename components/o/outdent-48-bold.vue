<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo6zpuchv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mo6zpuchv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:outdent-48-bold" /></template>
