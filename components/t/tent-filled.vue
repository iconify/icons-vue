<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq0lvb2-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kq0lvb2-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tent-filled" /></template>
