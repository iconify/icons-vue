<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1gq8obfz.css';
import '../../css/v/vil7ki9ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1gq8obfz"/><path class="vil7ki9ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wallet-48-bold" /></template>
