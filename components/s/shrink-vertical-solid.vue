<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkxv-k3lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkxv-k3lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shrink-vertical-solid" /></template>
