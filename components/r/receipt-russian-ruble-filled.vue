<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir0ltxjco.css';
import '../../css/c/c-llp8bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir0ltxjco"/><path clip-rule="evenodd" class="c-llp8bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-russian-ruble-filled" /></template>
