<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_cif6b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_cif6b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server-filled" /></template>
