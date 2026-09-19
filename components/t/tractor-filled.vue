<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-3y_nbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-3y_nbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tractor-filled" /></template>
