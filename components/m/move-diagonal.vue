<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmdfxvbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmdfxvbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:move-diagonal" /></template>
