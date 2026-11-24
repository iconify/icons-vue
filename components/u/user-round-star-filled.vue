<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qopej0bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qopej0bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-star-filled" /></template>
