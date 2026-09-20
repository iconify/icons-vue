<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6bmbpbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6bmbpbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:repeat-once" /></template>
