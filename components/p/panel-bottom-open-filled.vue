<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx7ywibap.css';
import '../../css/y/y4--wuesr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx7ywibap"/><path clip-rule="evenodd" class="y4--wuesr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-bottom-open-filled" /></template>
