<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnpjfhobm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lnpjfhobm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-exclamation-point" /></template>
