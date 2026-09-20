<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp1tbeg2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp1tbeg2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:onion" /></template>
