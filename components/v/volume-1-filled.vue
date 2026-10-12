<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-r3gkb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-r3gkb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:volume-1-filled" /></template>
