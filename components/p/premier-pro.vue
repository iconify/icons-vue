<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5maixbua.css';
import '../../css/b/bfq0sui_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5maixbua"/><path class="bfq0sui_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:premier-pro" /></template>
