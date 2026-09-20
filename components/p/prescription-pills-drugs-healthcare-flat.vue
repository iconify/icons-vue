<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dol_h130o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dol_h130o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:prescription-pills-drugs-healthcare-flat" /></template>
