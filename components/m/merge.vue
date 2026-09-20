<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsucofb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wsucofb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:merge" /></template>
