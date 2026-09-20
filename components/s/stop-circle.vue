<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1gz5sbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o1gz5sbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stop-circle" /></template>
