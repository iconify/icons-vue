<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nca5e5b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nca5e5b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-minus-fill" /></template>
