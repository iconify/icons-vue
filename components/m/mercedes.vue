<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj9qltbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj9qltbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mercedes" /></template>
