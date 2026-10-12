<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujzfkkbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujzfkkbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shopping-basket-filled" /></template>
