<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aimebubco.css';
import '../../css/o/ova0c4bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aimebubco"/><path class="ova0c4bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shipment-search-bold" /></template>
