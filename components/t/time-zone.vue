<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppyuwyb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ppyuwyb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:time-zone" /></template>
