<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu_fc-r2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nu_fc-r2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trellis" /></template>
