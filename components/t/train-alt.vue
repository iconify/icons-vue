<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihh-fxb0c.css';
import '../../css/x/xt343bbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ihh-fxb0c"/><path class="xt343bbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:train-alt" /></template>
