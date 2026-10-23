<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq-etymya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq-etymya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:midi-port" /></template>
