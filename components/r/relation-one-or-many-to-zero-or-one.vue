<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbw18bb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbw18bb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-one-or-many-to-zero-or-one" /></template>
