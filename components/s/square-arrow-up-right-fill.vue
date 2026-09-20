<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw_pfl42f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nw_pfl42f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-up-right-fill" /></template>
