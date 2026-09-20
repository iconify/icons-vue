<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9iu80bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m9iu80bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:zoom-in-fill" /></template>
