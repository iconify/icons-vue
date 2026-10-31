<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu76w6b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cu76w6b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-right-20-solid" /></template>
