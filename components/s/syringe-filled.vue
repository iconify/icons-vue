<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icu7jvbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="icu7jvbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:syringe-filled" /></template>
