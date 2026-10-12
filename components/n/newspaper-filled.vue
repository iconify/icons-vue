<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr46c6bmn.css';
import '../../css/v/v5th-uitq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr46c6bmn"/><path clip-rule="evenodd" class="v5th-uitq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:newspaper-filled" /></template>
