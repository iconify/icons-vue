<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_og5fbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_og5fbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:shield-alt-2" /></template>
