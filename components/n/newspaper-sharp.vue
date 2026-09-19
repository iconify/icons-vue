<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-_7j5bcq.css';
import '../../css/x/x-uz1nb-i.css';
import '../../css/y/ym9wp7_vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="n-_7j5bcq"/><path class="x-uz1nb-i"/><path class="ym9wp7_vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:newspaper-sharp" /></template>
