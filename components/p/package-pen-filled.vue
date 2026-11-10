<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dktvvbced.css';
import '../../css/m/msy_44tas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dktvvbced"/><path clip-rule="evenodd" class="msy_44tas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:package-pen-filled" /></template>
