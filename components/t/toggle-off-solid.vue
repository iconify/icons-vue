<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz8wqzpgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fz8wqzpgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:toggle-off-solid" /></template>
