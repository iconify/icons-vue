<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikcwavbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikcwavbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:spotlight-beam" /></template>
