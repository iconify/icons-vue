<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhekk-bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhekk-bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:programming-filled" /></template>
