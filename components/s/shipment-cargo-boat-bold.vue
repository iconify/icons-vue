<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcmznibzp.css';
import '../../css/o/of6h3jbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcmznibzp"/><path class="of6h3jbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shipment-cargo-boat-bold" /></template>
