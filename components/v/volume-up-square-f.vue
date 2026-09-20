<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmm2mib0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="cmm2mib0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:volume-up-square-f" /></template>
