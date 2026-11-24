<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6f3dfbkt.css';
import '../../css/a/a67_ne9yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6f3dfbkt"/><path class="a67_ne9yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:nut-off-filled" /></template>
