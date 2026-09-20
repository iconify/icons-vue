<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7rfoxnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az7rfoxnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-plus" /></template>
