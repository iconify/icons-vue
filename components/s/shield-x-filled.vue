<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajqb8bb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ajqb8bb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-x-filled" /></template>
