<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bawdxi5dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bawdxi5dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-radical-duotone" /></template>
