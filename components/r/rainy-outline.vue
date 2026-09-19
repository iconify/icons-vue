<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppih4zbbb.css';
import '../../css/o/o92kdvbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ppih4zbbb"/><path class="o92kdvbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:rainy-outline" /></template>
