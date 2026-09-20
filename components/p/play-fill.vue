<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg6xhabdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg6xhabdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:play-fill" /></template>
