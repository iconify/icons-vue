<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pna77acaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pna77acaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mdb" /></template>
