<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-qbgtbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-qbgtbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:vibrate-filled" /></template>
