<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc6_pdb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc6_pdb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:table-cells-merge" /></template>
