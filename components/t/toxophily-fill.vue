<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3l3htmku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b3l3htmku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toxophily-fill" /></template>
