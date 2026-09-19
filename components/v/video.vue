<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p73_1l57v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p73_1l57v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:video" /></template>
