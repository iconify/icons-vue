<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6d0c85zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o6d0c85zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-left-20-solid" /></template>
