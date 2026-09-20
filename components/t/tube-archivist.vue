<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb_obpjbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb_obpjbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tube-archivist" /></template>
