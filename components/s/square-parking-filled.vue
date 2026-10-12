<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb3rc9oyk.css';
import '../../css/g/glve-ra-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb3rc9oyk"/><path clip-rule="evenodd" class="glve-ra-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-parking-filled" /></template>
