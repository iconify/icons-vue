<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6vyhu-he.css';
import '../../css/t/tm33md3wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6vyhu-he"/><path class="tm33md3wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-bold" /></template>
