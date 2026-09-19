<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdsb_nbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdsb_nbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:sd-card-filled" /></template>
