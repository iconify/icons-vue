<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4ra0ur2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p4ra0ur2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sayana-press-outline-24px" /></template>
