<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvyg7g7cd.css';
import '../../css/s/s-t14rbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvyg7g7cd"/><path clip-rule="evenodd" class="s-t14rbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rocket-filled" /></template>
