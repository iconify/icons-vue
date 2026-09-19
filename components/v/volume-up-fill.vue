<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo_ygpbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lo_ygpbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:volume-up-fill" /></template>
