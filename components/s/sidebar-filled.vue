<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3m2r0nxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3m2r0nxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sidebar-filled" /></template>
