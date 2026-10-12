<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z32nf-brq.css';
import '../../css/h/h48_73b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z32nf-brq"/><path clip-rule="evenodd" class="h48_73b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tractor-filled" /></template>
