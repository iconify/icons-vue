<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo1ckdrso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jo1ckdrso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tickets-plane-filled" /></template>
