<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un5g80wwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="un5g80wwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stroke-line-join-miter-filled" /></template>
