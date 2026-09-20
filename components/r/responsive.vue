<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5j1sob3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5j1sob3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:responsive" /></template>
