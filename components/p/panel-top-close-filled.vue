<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhp68vbqz.css';
import '../../css/v/vif4xej-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xhp68vbqz"/><path class="vif4xej-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-top-close-filled" /></template>
