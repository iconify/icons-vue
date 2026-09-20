<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq0xcgf7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uq0xcgf7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pipette" /></template>
