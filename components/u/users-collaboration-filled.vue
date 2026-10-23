<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2getkc1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2getkc1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:users-collaboration-filled" /></template>
