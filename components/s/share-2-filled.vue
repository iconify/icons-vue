<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrf45hb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrf45hb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:share-2-filled" /></template>
