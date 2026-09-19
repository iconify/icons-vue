<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps7l495qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ps7l495qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:phone-outline" /></template>
