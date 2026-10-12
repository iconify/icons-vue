<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr-36obqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr-36obqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scale-filled" /></template>
