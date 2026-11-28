<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn4cq5nxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn4cq5nxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:washing-machine-alert" /></template>
