<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axvkndb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axvkndb_w primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:route-x-duotone" /></template>
