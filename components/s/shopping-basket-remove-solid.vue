<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8kwj8n9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8kwj8n9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shopping-basket-remove-solid" /></template>
