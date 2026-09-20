<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu4rbsbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu4rbsbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pencil-1" /></template>
