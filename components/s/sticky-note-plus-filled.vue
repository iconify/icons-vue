<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcro2yo8e.css';
import '../../css/a/aju00ib0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcro2yo8e"/><path class="aju00ib0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sticky-note-plus-filled" /></template>
