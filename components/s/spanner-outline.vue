<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqlamj4tr.css';
import '../../css/c/ctcmn9izu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="uqlamj4tr"/><path class="ctcmn9izu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:spanner-outline" /></template>
