<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx7ywibap.css';
import '../../css/l/l7g6jsgpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx7ywibap"/><path clip-rule="evenodd" class="l7g6jsgpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-bottom-close-filled" /></template>
