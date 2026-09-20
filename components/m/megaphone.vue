<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3by0zb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="w3by0zb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:megaphone" /></template>
