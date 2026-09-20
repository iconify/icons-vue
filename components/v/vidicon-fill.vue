<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crdgngbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crdgngbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vidicon-fill" /></template>
