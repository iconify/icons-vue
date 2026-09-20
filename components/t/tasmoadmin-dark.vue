<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuxatb8ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uuxatb8ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tasmoadmin-dark" /></template>
