<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh5dizfkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh5dizfkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sticky-note-check" /></template>
