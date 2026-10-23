<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7orblb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7orblb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scale-3d" /></template>
