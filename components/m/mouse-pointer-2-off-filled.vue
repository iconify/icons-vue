<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im7p7qbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im7p7qbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-pointer-2-off-filled" /></template>
