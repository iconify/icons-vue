<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqil5bbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oqil5bbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:res-4k-filled" /></template>
