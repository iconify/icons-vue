<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay8cjh3ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay8cjh3ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-half-fill" /></template>
