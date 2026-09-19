<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz9kydbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz9kydbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:playlist-03" /></template>
