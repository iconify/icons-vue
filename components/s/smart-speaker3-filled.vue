<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psukv_bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psukv_bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smart-speaker3-filled" /></template>
