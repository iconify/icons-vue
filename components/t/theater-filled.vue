<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt_6_ccuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt_6_ccuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:theater-filled" /></template>
