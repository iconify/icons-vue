<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi05xubmo.css';
import '../../css/a/a2uu82b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yi05xubmo"/><path clip-rule="evenodd" class="a2uu82b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:undo-outline" /></template>
