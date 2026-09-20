<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtlt29bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jtlt29bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:share-24" /></template>
