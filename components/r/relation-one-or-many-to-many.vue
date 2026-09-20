<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpb8lgbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpb8lgbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-one-or-many-to-many" /></template>
