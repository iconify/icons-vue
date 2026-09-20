<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4vpuwblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c4vpuwblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-sparkle-fill" /></template>
