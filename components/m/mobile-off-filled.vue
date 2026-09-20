<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0gpw2vbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n0gpw2vbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mobile-off-filled" /></template>
