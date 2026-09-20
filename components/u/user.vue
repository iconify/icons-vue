<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwzk5mtti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwzk5mtti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:user" /></template>
