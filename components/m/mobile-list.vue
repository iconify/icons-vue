<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv7e-pbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv7e-pbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mobile-list" /></template>
