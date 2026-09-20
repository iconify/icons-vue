<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6ad7xqxj.css';
import '../../css/p/p7e-r07_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q6ad7xqxj"/><path class="p7e-r07_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pfsense" /></template>
