<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0wi0dc7i.css';
import '../../css/p/p2_f0-rsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0wi0dc7i"/><path class="p2_f0-rsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rotten-tomatoes" /></template>
