<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z69k3lb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z69k3lb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tile" /></template>
