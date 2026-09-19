<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzdt_tbkb.css';
import '../../css/u/uh6i7ubar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzdt_tbkb"/><path class="uh6i7ubar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:pin-outline" /></template>
