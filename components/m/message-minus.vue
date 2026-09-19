<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go9b1n-cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go9b1n-cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:message-minus" /></template>
