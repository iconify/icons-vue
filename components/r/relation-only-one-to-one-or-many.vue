<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbp78cmjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbp78cmjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-only-one-to-one-or-many" /></template>
