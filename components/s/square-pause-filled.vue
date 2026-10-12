<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twrw249du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="twrw249du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-pause-filled" /></template>
