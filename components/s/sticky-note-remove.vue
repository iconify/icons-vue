<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b70_0tbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b70_0tbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticky-note-remove" /></template>
