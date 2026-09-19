<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8fqnnf_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="z8fqnnf_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:stairs" /></template>
