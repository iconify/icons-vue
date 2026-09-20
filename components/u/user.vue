<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu3kl0h8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu3kl0h8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:user" /></template>
