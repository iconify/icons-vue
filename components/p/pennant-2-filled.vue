<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r43v05j1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r43v05j1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pennant-2-filled" /></template>
