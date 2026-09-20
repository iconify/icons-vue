<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li-jbvb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="li-jbvb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:scale-unbalance" /></template>
