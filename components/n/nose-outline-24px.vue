<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qluhj6bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qluhj6bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nose-outline-24px" /></template>
