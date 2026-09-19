<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrji-ib2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="lrji-ib2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-skiing-nordic" /></template>
