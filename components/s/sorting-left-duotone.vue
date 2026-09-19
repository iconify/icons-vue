<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byo-9pbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byo-9pbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sorting-left-duotone" /></template>
