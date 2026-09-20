<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egq5z7b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egq5z7b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sparkles" /></template>
