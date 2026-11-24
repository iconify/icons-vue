<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tctg72b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tctg72b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:paper-bag-filled" /></template>
