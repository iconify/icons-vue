<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy2zsfmxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy2zsfmxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:relation-many-to-many-filled" /></template>
