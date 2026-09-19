<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnl2u0pbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnl2u0pbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:storage-class" /></template>
