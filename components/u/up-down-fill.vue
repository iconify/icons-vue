<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bioncxr9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bioncxr9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:up-down-fill" /></template>
