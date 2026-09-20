<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_6mmuz-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_6mmuz-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-wrap-disabled" /></template>
