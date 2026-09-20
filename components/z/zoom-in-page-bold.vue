<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg-3vud6u.css';
import '../../css/p/p04h_vw0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg-3vud6u"/><path class="p04h_vw0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:zoom-in-page-bold" /></template>
