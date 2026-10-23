<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlei7i_rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlei7i_rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:volume" /></template>
