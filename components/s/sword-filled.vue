<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqnd5b4rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqnd5b4rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sword-filled" /></template>
