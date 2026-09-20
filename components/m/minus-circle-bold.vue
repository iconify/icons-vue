<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5qw40bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5qw40bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minus-circle-bold" /></template>
