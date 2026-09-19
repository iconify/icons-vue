<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szo_c1lgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szo_c1lgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:octagon-help" /></template>
