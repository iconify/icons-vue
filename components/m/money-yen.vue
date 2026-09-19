<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq_d5mb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="iq_d5mb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:money-yen" /></template>
