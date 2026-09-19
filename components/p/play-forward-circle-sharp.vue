<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icacskyay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="icacskyay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-forward-circle-sharp" /></template>
