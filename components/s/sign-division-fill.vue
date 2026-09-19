<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i03poyb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i03poyb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-division-fill" /></template>
