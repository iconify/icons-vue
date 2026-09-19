<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcgcfnc6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcgcfnc6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shopping-bag-arrow-down" /></template>
