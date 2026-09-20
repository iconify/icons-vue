<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kudk1ganc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kudk1ganc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mobilizon-light" /></template>
