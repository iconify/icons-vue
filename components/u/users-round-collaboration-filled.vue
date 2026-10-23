<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-o7nuz9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-o7nuz9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:users-round-collaboration-filled" /></template>
