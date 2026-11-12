<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajrotabeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ajrotabeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-light" /></template>
