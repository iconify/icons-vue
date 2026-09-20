<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3er0flzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3er0flzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smartfox-light" /></template>
