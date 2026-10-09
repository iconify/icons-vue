<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d26h8nnid.css';
import '../../css/p/py89-ib0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d26h8nnid"/><path class="py89-ib0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pallet-20-bold" /></template>
