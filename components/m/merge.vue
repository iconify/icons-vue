<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_7t4ubcy.css';
import '../../css/d/dbpvorrsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_7t4ubcy"/><path class="dbpvorrsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:merge" /></template>
