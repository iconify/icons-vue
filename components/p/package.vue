<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqm994blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqm994blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:package" /></template>
