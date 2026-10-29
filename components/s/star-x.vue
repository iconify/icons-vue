<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdb_vssxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdb_vssxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:star-x" /></template>
