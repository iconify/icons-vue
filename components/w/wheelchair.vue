<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi2p-lb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pi2p-lb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:wheelchair" /></template>
