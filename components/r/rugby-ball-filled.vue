<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t01_zdb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t01_zdb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rugby-ball-filled" /></template>
