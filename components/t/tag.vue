<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn655r21a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dn655r21a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:tag" /></template>
