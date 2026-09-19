<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r79y_fa2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r79y_fa2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:shield-off-fill" /></template>
