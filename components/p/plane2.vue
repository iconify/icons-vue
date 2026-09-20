<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aepfsacgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aepfsacgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plane2" /></template>
