<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j27j2c08b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j27j2c08b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:paperclip" /></template>
