<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb7520byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kb7520byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:telescope" /></template>
