<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bigdc0bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bigdc0bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:message-solid" /></template>
