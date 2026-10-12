<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va-b4i6ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="va-b4i6ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-bottom-dashed-filled" /></template>
