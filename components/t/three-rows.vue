<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayka6ccdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayka6ccdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:three-rows" /></template>
