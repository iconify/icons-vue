<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnd4zcbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnd4zcbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:redo-solid" /></template>
