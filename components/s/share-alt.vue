<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alh4-efxe.css';
import '../../css/p/p6thd6bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="alh4-efxe"/><path class="p6thd6bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:share-alt" /></template>
