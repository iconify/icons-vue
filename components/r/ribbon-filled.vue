<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p59uvebzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p59uvebzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ribbon-filled" /></template>
