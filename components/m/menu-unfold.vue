<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suyzr6jpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="suyzr6jpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:menu-unfold" /></template>
