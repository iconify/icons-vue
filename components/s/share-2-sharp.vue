<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4p6zwb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4p6zwb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:share-2-sharp" /></template>
