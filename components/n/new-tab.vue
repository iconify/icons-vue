<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw_44nilr.css';
import '../../css/v/v9zanyf3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uw_44nilr"/><path class="v9zanyf3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:new-tab" /></template>
