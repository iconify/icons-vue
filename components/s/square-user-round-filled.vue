<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjfvhn6ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjfvhn6ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-user-round-filled" /></template>
