<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9vgl2lhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9vgl2lhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-left-solid" /></template>
