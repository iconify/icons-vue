<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-if3ugxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="x-if3ugxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:stop" /></template>
