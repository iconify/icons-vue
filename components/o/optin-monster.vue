<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqc-qrqqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="gqc-qrqqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:optin-monster" /></template>
