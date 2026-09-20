<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4f9tbg5g.css';
import '../../css/v/v8p-pjnia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4f9tbg5g"/><path class="v8p-pjnia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shipment-bold" /></template>
