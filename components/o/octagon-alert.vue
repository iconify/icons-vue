<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj9s4025x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj9s4025x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:octagon-alert" /></template>
