<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjdt1_b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjdt1_b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sort-desc" /></template>
