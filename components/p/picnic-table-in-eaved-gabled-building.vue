<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_bwp5i_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t_bwp5i_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:picnic-table-in-eaved-gabled-building" /></template>
