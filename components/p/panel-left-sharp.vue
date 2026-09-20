<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2bd2pq2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2bd2pq2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-sharp" /></template>
