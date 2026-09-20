<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1smw0s4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a1smw0s4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:star-circle-remix" /></template>
