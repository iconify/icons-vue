<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1_nssb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="t1_nssb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:share-from-square" /></template>
