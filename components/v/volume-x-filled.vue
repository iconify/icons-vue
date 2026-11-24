<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krsa40z7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krsa40z7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:volume-x-filled" /></template>
