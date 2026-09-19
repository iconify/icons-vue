<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bob346bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bob346bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:push-chevron-up-o" /></template>
