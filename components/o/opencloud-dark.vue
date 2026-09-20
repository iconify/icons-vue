<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/risct0b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="risct0b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opencloud-dark" /></template>
