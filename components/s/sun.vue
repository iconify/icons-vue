<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojke0rlcu.css';
import '../../css/o/ocbn0jbob.css';
import '../../css/v/vggz4i0-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer ojke0rlcu"/><path class="duoicon-secondary-layer ocbn0jbob"/><path class="duoicon-primary-layer vggz4i0-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:sun" /></template>
