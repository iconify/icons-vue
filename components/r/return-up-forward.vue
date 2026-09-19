<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nib94r23y.css';
import '../../css/t/tp8s31b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nib94r23y"/><path class="tp8s31b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:return-up-forward" /></template>
