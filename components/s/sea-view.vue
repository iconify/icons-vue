<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxon0y14n.css';
import '../../css/u/uwoztrbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxon0y14n"/><path class="uwoztrbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sea-view" /></template>
