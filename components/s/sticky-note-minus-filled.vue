<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk_0rpbzb.css';
import '../../css/r/r67ffobwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk_0rpbzb"/><path class="r67ffobwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sticky-note-minus-filled" /></template>
