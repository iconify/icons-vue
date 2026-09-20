<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qja8evbtd.css';
import '../../css/q/qitu6dbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qja8evbtd"/><path class="qitu6dbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-velocity-dark" /></template>
