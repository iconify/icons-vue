<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxom58b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxom58b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:siren" /></template>
