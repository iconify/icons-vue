<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve4n1njjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ve4n1njjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:shield-alt" /></template>
