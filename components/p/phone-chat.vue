<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkraa1b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkraa1b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-chat" /></template>
