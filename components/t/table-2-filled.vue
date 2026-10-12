<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt23idoxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt23idoxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:table-2-filled" /></template>
