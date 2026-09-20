<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux25dn--w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ux25dn--w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openchangelog-light" /></template>
