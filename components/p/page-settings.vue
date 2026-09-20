<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aerf2dljn.css';
import '../../css/p/p27qq8biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aerf2dljn"/><path class="p27qq8biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:page-settings" /></template>
