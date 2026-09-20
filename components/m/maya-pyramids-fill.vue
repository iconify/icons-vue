<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pelcyhb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pelcyhb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:maya-pyramids-fill" /></template>
