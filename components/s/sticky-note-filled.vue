<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaqykgbsd.css';
import '../../css/n/nbhl3j1uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaqykgbsd"/><path class="nbhl3j1uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sticky-note-filled" /></template>
