<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbs5-sbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbs5-sbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toolbox" /></template>
