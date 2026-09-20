<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7-blbuve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7-blbuve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-many-to-one-or-many" /></template>
