<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1-e7co-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1-e7co-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-crt" /></template>
