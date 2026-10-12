<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bro2fcb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bro2fcb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:spool-filled" /></template>
