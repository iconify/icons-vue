<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmqtb0_hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmqtb0_hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:vuejs-alt" /></template>
