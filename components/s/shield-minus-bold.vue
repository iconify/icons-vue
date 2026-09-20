<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh--6bbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sh--6bbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minus-bold" /></template>
