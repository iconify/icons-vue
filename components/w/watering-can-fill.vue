<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b68sjcc4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b68sjcc4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:watering-can-fill" /></template>
