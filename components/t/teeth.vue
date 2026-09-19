<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbxo4ubsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="vbxo4ubsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:teeth" /></template>
