<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnjp8bb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnjp8bb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:supabase" /></template>
