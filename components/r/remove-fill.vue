<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9l5ethsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t9l5ethsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:remove-fill" /></template>
