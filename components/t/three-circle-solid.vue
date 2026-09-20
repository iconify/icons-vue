<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovf2g8dss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovf2g8dss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:three-circle-solid" /></template>
