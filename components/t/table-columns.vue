<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqpsb7bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mqpsb7bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:table-columns" /></template>
