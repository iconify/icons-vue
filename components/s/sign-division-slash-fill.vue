<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n12cj6bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n12cj6bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-division-slash-fill" /></template>
