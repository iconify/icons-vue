<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bykugi_jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bykugi_jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:plane-landing-filled" /></template>
