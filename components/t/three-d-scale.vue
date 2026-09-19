<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwpp8ccpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwpp8ccpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:three-d-scale" /></template>
