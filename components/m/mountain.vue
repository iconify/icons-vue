<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urw_vubil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urw_vubil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mountain" /></template>
