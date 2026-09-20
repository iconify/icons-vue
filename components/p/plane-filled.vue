<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bax00np5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bax00np5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plane-filled" /></template>
