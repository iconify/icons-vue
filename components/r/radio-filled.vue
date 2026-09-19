<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_dm36b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_dm36b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:radio-filled" /></template>
