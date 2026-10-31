<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo19-_b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo19-_b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sidebar-gloss" /></template>
