<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q51nucinw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q51nucinw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sidebar-alt-filled" /></template>
