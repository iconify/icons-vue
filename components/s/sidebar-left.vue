<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-32aobnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-32aobnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-left" /></template>
