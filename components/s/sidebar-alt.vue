<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg3qi_knx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cg3qi_knx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sidebar-alt" /></template>
