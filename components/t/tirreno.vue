<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4gv-v-ly.css';
import '../../css/u/uwxio7x7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x4gv-v-ly"/><path class="uwxio7x7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tirreno" /></template>
