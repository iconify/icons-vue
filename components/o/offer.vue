<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afyhz4brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afyhz4brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:offer" /></template>
