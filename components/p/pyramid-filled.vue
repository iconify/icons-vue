<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naw7gvbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="naw7gvbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pyramid-filled" /></template>
