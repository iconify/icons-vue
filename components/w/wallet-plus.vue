<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meq_0c5ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meq_0c5ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wallet-plus" /></template>
