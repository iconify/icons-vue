<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unfk_pn7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="unfk_pn7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paperclip4-filled" /></template>
