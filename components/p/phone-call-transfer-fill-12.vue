<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo7_onhnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yo7_onhnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-transfer-fill-12" /></template>
