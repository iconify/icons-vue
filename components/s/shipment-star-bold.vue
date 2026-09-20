<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywkgkr1pi.css';
import '../../css/s/slgmhktay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywkgkr1pi"/><path class="slgmhktay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shipment-star-bold" /></template>
