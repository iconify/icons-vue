<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwwdm_2ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwwdm_2ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pen-clip" /></template>
