<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8cu1vnkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8cu1vnkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-filled" /></template>
