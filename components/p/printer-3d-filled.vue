<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv1gfqbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yv1gfqbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:printer-3d-filled" /></template>
