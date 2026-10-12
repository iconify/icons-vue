<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7zwfz7lk.css';
import '../../css/n/nbhl3j1uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t7zwfz7lk"/><path class="nbhl3j1uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sticker-filled" /></template>
