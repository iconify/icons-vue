<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8o-8jgtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8o-8jgtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:swords-filled" /></template>
