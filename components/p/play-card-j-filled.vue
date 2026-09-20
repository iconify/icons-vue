<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh3gl-b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh3gl-b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-j-filled" /></template>
