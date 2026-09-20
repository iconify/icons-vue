<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm5vguepc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hm5vguepc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:osf" /></template>
