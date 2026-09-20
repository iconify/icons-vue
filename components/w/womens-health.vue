<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amcb6ybaq.css';
import '../../css/k/kasw7ebxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="amcb6ybaq"/><path class="kasw7ebxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:womens-health" /></template>
