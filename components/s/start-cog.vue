<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp_nqwbll.css';
import '../../css/p/p99jesbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sp_nqwbll"/><path class="p99jesbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:start-cog" /></template>
