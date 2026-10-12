<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls-mqmbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls-mqmbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:volume-off-filled" /></template>
