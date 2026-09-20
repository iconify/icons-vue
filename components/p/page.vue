<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_3-kybfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_3-kybfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:page" /></template>
