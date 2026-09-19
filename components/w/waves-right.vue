<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppyevyb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ppyevyb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:waves-right" /></template>
