<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwoeytogu.css';
import '../../css/c/cc3fl7wwz.css';
import '../../css/x/xul7skbaf.css';
import '../../css/k/k6fth3b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwoeytogu"/><circle class="cc3fl7wwz"/><circle class="xul7skbaf"/><circle class="k6fth3b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:th-list" /></template>
