<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7c4exb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x7c4exb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speech-balloon-info-small-filled" /></template>
