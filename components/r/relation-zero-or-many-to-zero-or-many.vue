<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgk128bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgk128bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-zero-or-many-to-zero-or-many" /></template>
