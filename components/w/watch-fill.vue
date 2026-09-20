<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgz6b35js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgz6b35js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:watch-fill" /></template>
