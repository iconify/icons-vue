<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au0ie6bpn.css';
import '../../css/l/l4ovptbip.css';
import '../../css/q/qkmfhjfvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="au0ie6bpn"/><path class="l4ovptbip"/><path class="qkmfhjfvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:stop-cog" /></template>
