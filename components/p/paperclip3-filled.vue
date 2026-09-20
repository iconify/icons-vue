<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cusa6cggl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cusa6cggl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paperclip3-filled" /></template>
