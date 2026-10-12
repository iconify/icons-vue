<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as-dgnbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="as-dgnbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:octagon-minus-filled" /></template>
