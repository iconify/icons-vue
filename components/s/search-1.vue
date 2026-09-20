<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdlmnabbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="mdlmnabbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:search-1" /></template>
