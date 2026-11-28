<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8mw0_b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8mw0_b-c primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:reply-all-duotone" /></template>
