<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye6zn_bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye6zn_bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-lucca-alt-below" /></template>
